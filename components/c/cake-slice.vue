<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv0rw9uug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv0rw9uug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cake-slice" /></template>
