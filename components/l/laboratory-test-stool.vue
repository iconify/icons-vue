<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpbemslgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpbemslgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:laboratory-test-stool" /></template>
