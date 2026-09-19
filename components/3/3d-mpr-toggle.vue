<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eziplt3ei.css';
import '../../css/n/ngzn0zb4p.css';
import '../../css/a/agt909hcp.css';
import '../../css/n/n469xpqan.css';
import '../../css/k/k-p36xbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eziplt3ei"/><path class="ngzn0zb4p"/><path class="agt909hcp"/><path class="n469xpqan"/><path class="k-p36xbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:3d-mpr-toggle" /></template>
