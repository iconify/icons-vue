<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a69cznbzg.css';
import '../../css/c/ckrv68b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a69cznbzg"/><path class="ckrv68b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bone-bold-duotone" /></template>
