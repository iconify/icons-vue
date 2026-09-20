<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acmwh1p4z.css';
import '../../css/e/e3v1inbws.css';
import '../../css/b/bbq7rkbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":64};
const content = `<path class="acmwh1p4z"/><path class="e3v1inbws"/><path class="bbq7rkbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:imaging-alternative-pet" /></template>
