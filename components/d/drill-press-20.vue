<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzaxycb1h.css';
import '../../css/w/wcn0uyb2b.css';
import '../../css/k/kl3kspb4p.css';
import '../../css/h/hu2xs9w1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gzaxycb1h"/><path class="wcn0uyb2b"/><path class="kl3kspb4p"/><path class="hu2xs9w1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drill-press-20" /></template>
