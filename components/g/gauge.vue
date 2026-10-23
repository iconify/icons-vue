<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/a/akztulxao.css';
import '../../css/i/ie61plbol.css';
import '../../css/c/cma6q9u3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="akztulxao"/><path class="ie61plbol"/><path class="cma6q9u3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:gauge" /></template>
