<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv14xiw-u.css';
import '../../css/z/zol642wmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv14xiw-u"/><path clip-rule="evenodd" class="zol642wmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-right-bold-duotone" /></template>
