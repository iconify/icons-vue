<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjdecabze.css';
import '../../css/v/vlj0scbpf.css';
import '../../css/d/d-2gb0bhq.css';
import '../../css/w/wi93bqmrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><clipPath id="SVGWfBvnzCF"><path class="tjdecabze"/></clipPath><symbol id="SVGYqAb8ZRw" viewBox="0 0 375 375"><circle class="vlj0scbpf"/><path class="d-2gb0bhq"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="0 187.5 187.5; 45 187.5 187.5"/></path></symbol></defs><g clip-path="url(#SVGWfBvnzCF)"><use width="375" height="375" href="#SVGYqAb8ZRw" transform="translate(68.5 104.5)"/></g><path class="wi93bqmrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:horizon" /></template>
