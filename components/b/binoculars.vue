<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djrforfsc.css';
import '../../css/l/lylrjtb6a.css';
import '../../css/a/ak97f6bnh.css';
import '../../css/o/opwr92bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djrforfsc wm-a"/><path class="lylrjtb6a wm-k"/><path class="ak97f6bnh wm-k"/><path class="opwr92bel wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:binoculars" /></template>
