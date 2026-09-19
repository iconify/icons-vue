<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwibdw4bb.css';
import '../../css/w/w0wj57jig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwibdw4bb"/><path class="w0wj57jig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dizzy" /></template>
