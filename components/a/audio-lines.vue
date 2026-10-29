<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk8cd_zmb.css';
import '../../css/s/stgarl9zm.css';
import '../../css/h/hd_apab9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk8cd_zmb wm-a"/><path class="stgarl9zm wm-k"/><path class="hd_apab9n wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:audio-lines" /></template>
