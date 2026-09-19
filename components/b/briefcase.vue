<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g72wj7u_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g72wj7u_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:briefcase" /></template>
