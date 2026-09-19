<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvq0zfibe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dvq0zfibe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:briefcase" /></template>
