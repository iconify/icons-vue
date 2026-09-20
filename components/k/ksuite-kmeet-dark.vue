<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wufabxb2f.css';
import '../../css/h/hafkb4bxt.css';
import '../../css/c/cdjzimb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wufabxb2f"/><path class="hafkb4bxt"/><path class="cdjzimb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kmeet-dark" /></template>
