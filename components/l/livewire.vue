<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcrd7-toh.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/j/jqpcl6bnj.css';
import '../../css/c/c07nn9b0c.css';
import '../../css/d/dmqd37b_t.css';
import '../../css/m/m2cahk2ih.css';
import '../../css/l/l-d7h-bcb.css';
import '../../css/n/nycd_gb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG5WCixdVh" class="tcrd7-toh"/></defs><use href="#SVG5WCixdVh" class="d2kvgvbvc"/><path class="jqpcl6bnj"/><path class="c07nn9b0c"/><use href="#SVG5WCixdVh" class="d2kvgvbvc"/><path class="dmqd37b_t"/><path class="m2cahk2ih"/><path class="l-d7h-bcb"/><path class="nycd_gb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:livewire" /></template>
