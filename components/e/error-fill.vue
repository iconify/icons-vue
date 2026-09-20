<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt2f7cbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gt2f7cbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:error-fill" /></template>
