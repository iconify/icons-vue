<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpc_n_8lm.css';
import '../../css/g/go4rm8bar.css';
import '../../css/r/r2dvf4bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpc_n_8lm"/><path class="go4rm8bar"/><path class="r2dvf4bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ghost-bold-duotone" /></template>
