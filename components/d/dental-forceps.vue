<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7v-nsz8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d7v-nsz8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:dental-forceps" /></template>
