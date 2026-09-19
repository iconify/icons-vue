<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idif-zbrp.css';
import '../../css/i/ivt8o-bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idif-zbrp"/><path class="ivt8o-bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:book-heart" /></template>
