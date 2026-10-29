<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yjzybdkuw.css';
import '../../css/e/efohs445y.css';
import '../../css/s/su76dvw1u.css';
import '../../css/a/ang3hpb4r.css';
import '../../css/q/qrwfd8ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k yjzybdkuw"/><path class="efohs445y wm-a"/><path class="su76dvw1u wm-shadow"/><path class="ang3hpb4r wm-k"/><path class="qrwfd8ber wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:golf-engrave" /></template>
