<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz66qlb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":466,"height":512};
const content = `<path class="pz66qlb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bithound" /></template>
