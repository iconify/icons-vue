<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cth7kpfnp.css';
import '../../css/a/azpullbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cth7kpfnp"/><path class="azpullbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bolt-bold-duotone" /></template>
