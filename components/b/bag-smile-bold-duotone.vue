<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg3heibao.css';
import '../../css/i/i9yzznx8e.css';
import '../../css/t/t1r1agbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg3heibao"/><path class="i9yzznx8e"/><path class="t1r1agbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-smile-bold-duotone" /></template>
