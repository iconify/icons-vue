<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnhwl-37f.css';
import '../../css/i/ipmkijbyf.css';
import '../../css/x/xsojoj1yq.css';
import '../../css/k/kai3f3bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mnhwl-37f"/><path class="ipmkijbyf"/><path class="xsojoj1yq"/><path class="kai3f3bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:honeybee" /></template>
