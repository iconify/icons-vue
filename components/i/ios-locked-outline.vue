<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fao0odb7l.css';
import '../../css/v/v-qvd4btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fao0odb7l"/><path class="v-qvd4btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-locked-outline" /></template>
