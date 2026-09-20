<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui-tk2bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui-tk2bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:grid-solid" /></template>
