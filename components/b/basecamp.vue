<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyyw8y90x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="wyyw8y90x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:basecamp" /></template>
