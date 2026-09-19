<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttatuib8i.css';
import '../../css/j/jdr9a7bii.css';
import '../../css/l/l04bb08wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttatuib8i"/><path class="jdr9a7bii"/><path class="l04bb08wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:apigee-sense" /></template>
