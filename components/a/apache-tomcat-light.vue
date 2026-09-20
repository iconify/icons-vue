<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp6zpdntm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp6zpdntm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-tomcat-light" /></template>
