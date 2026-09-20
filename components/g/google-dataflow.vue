<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5nf9jbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5nf9jbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-dataflow" /></template>
