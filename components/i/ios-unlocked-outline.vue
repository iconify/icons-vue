<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-qvd4btd.css';
import '../../css/i/izm7r3btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-qvd4btd"/><path class="izm7r3btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-unlocked-outline" /></template>
