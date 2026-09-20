<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jksnjxmjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jksnjxmjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:image-flash-off-flash-power-connect-charge-off-electricity-lightning" /></template>
