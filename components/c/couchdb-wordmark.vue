<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy6apqb-v.css';
import '../../css/r/ryas737co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xy6apqb-v"/><path class="ryas737co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:couchdb-wordmark" /></template>
