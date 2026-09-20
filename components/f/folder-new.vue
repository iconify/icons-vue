<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcypd9bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jcypd9bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-new" /></template>
