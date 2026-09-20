<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn29a_4bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hn29a_4bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:link-remove-solid" /></template>
