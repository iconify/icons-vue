<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj4pyrh1t.css';
import '../../css/h/h0-fzyzmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vj4pyrh1t"/><path class="h0-fzyzmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:heyform-dark" /></template>
