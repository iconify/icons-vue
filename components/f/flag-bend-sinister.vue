<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeunnbwrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aeunnbwrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:flag-bend-sinister" /></template>
