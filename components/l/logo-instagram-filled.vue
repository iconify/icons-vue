<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwuekqkoy.css';
import '../../css/x/x7a-2lu-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwuekqkoy"/><path class="x7a-2lu-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-instagram-filled" /></template>
