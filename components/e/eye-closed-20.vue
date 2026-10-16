<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1j29iy8v.css';
import '../../css/g/gljfs3bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1j29iy8v"/><path class="gljfs3bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-closed-20" /></template>
