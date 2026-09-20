<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/ann80wu5h.css';
import '../../css/b/b8oyz2b-k.css';
import '../../css/f/fllxh0mbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ann80wu5h"/><rect transform="rotate(180 19.75 16.25)" class="b8oyz2b-k"/><rect transform="rotate(180 10.25 21.25)" class="fllxh0mbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:align-top" /></template>
