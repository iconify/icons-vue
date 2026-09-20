<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp52dj2tx.css';
import '../../css/y/y5ok-dbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fp52dj2tx"/><path class="y5ok-dbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon" /></template>
