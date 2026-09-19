<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zho1-hbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zho1-hbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dice-three" /></template>
