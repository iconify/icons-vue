<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/w/w0ylnq.css';
import '../../css/e/eky6zv.css';
import '../../css/y/y4wbml.css';
import '../../css/f/fr5r9e.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew w0ylnq"/><path class="eky6zv iw1iew y4wbml"/><path class="fr5r9e iw1iew y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:filter-remove-filled" /></template>
