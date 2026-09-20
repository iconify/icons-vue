<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk585tbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk585tbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coin-3-fill" /></template>
