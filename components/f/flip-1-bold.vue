<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/i/idvi9abbj.css';
import '../../css/g/gfl6m_b2c.css';
import '../../css/k/kb5hnv1mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="idvi9abbj"/><path class="gfl6m_b2c"/><path class="kb5hnv1mt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:flip-1-bold" /></template>
