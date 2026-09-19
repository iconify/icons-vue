<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-ieokedw.css';
import '../../css/g/gg4gf7b6h.css';
import '../../css/e/ea354ccpf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 h-ieokedw"/><path class="clr-i-outline clr-i-outline-path-2 gg4gf7b6h"/><path class="clr-i-outline clr-i-outline-path-3 ea354ccpf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:align-top-line" /></template>
