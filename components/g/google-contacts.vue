<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5skjynkm.css';
import '../../css/h/h6v6gtwle.css';
import '../../css/t/txlc9qs6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5skjynkm"/><path class="h6v6gtwle"/><path class="txlc9qs6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-contacts" /></template>
