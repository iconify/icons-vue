<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wcybux_3z.css';
import '../../css/a/abcwoxbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="wcybux_3z"/><path class="abcwoxbsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:down-left" /></template>
