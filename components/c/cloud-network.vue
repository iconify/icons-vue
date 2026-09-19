<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/codahaulz.css';
import '../../css/b/b54uexayv.css';
import '../../css/e/edas0ubvn.css';
import '../../css/a/a3mos-bte.css';
import '../../css/d/dde9wca7b.css';
import '../../css/e/ei_yh8byn.css';
import '../../css/b/b6is_enxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="codahaulz"/><path class="b54uexayv"/><circle class="edas0ubvn"/><circle class="a3mos-bte"/><path class="dde9wca7b"/><circle class="ei_yh8byn"/><circle class="b6is_enxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-network" /></template>
