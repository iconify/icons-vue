<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plwc2obrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plwc2obrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:book-open-fill" /></template>
