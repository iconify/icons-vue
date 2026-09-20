<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciwhunbto.css';
import '../../css/s/sdgejvbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ciwhunbto"/><path class="sdgejvbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:exit" /></template>
