<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyfuaq7jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyfuaq7jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lining" /></template>
