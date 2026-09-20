<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9xki7bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9xki7bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:folder-check-fill" /></template>
