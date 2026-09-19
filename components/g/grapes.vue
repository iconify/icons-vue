<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a__c8zpwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a__c8zpwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:grapes" /></template>
