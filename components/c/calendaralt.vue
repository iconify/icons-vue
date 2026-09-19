<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9q3a_dks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k9q3a_dks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:calendaralt" /></template>
