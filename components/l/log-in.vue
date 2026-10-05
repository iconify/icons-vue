<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/fn3g3ebng.css';
import '../../css/e/enrflx9dd.css';
import '../../css/g/gtw2eeblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="fn3g3ebng"/><path class="enrflx9dd"/><path class="gtw2eeblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:log-in" /></template>
