<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlis81b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlis81b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:application" /></template>
