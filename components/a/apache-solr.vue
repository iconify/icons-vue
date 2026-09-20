<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvejc9b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvejc9b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-solr" /></template>
