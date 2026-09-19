<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/f/f_zukwb7p.css';
import '../../css/i/iitlfdb5a.css';
import '../../css/x/xxddg2bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsCe0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsCe0)"><path class="f_zukwb7p"/><path class="iitlfdb5a"/><path class="xxddg2bhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:ce" /></template>
