<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5xb7ebsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5xb7ebsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:banknotes-filled" /></template>
