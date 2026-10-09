<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fspafybgd.css';
import '../../css/f/fw66xi3qj.css';
import '../../css/a/ayok7_nhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fspafybgd"/><path class="fw66xi3qj"/><path class="ayok7_nhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:houseboat-20-bold" /></template>
