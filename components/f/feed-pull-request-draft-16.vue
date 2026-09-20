<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg_pavb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gg_pavb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-pull-request-draft-16" /></template>
