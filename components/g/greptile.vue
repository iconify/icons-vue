<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjk9rcuob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kjk9rcuob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:greptile" /></template>
