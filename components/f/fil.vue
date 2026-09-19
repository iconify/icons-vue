<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/d/diqeztb6w.css';
import '../../css/p/prjwigbsg.css';
import '../../css/z/z19bf84dj.css';
import '../../css/j/jbp6xqbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsFil0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsFil0)"><path class="diqeztb6w"/><path class="prjwigbsg"/><path class="z19bf84dj"/><path class="jbp6xqbph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:fil" /></template>
