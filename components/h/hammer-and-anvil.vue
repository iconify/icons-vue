<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljo6bmi5v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnhDFZccx"><path class="ljo6bmi5v"/></mask></defs><path mask="url(#SVGnhDFZccx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hammer-and-anvil" /></template>
