<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/d/d9kplxbfn.css';
import '../../css/a/a5r5lvb1n.css';
import '../../css/p/plpw9sb1i.css';
import '../../css/b/b6cya0bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="d9kplxbfn"/><path class="a5r5lvb1n"/><path class="plpw9sb1i"/><path class="b6cya0bdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:brush" /></template>
