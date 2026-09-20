<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojszwubqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojszwubqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:folder-cross-fill" /></template>
