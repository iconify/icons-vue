<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lrke56x2n.css';
import '../../css/b/b62s-qcfq.css';
import '../../css/f/flj7hj2gq.css';
import '../../css/o/ot9di8qwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lrke56x2n wm-shadow"/><path class="b62s-qcfq wm-shadow"/><path class="flj7hj2gq"/><path class="ot9di8qwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:filter" /></template>
