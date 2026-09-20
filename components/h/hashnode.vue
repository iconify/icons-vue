<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9xurqb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path clip-rule="evenodd" class="n9xurqb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hashnode" /></template>
