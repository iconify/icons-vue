<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs5ix9gtg.css';
import '../../css/s/s3kax5bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs5ix9gtg"/><path class="s3kax5bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:creators-club-light" /></template>
