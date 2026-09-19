<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj43_vuli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qj43_vuli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:eye-slash" /></template>
