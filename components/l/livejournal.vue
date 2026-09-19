<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btnvbfz_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":488};
const content = `<path class="btnvbfz_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:livejournal" /></template>
