<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/asbi602zl.css';
import '../../css/f/fr2owub7s.css';
import '../../css/k/kfd4e9bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="asbi602zl"/><path class="fr2owub7s"/><path class="kfd4e9bhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:brush2" /></template>
