<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ileo9db7a.css';
import '../../css/i/i3l80h-5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ileo9db7a"/><path class="i3l80h-5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-bold-duotone" /></template>
