<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8ss_jbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m8ss_jbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hdd-rack-fill" /></template>
