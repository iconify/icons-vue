<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diysz0ups.css';
import '../../css/j/jvrog61rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diysz0ups"/><path class="jvrog61rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:dollar" /></template>
