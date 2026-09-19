<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx1_gabtl.css';
import '../../css/j/jk0rnfymy.css';
import '../../css/i/io_0phpjr.css';
import '../../css/f/fuatp5wib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx1_gabtl"/><path class="jk0rnfymy"/><path class="io_0phpjr"/><path class="fuatp5wib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:automl" /></template>
