<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6mtzcc9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6mtzcc9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:credit-card-fill" /></template>
