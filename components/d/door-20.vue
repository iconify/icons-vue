<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqvv3bb7y.css';
import '../../css/t/ti-bis8gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kqvv3bb7y"/><path class="ti-bis8gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:door-20" /></template>
