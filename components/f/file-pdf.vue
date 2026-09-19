<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/updz07b-a.css';
import '../../css/g/g8ph7i0bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="updz07b-a"/><path class="g8ph7i0bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-pdf" /></template>
