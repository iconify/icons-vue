<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/aw8asbupg.css';
import '../../css/k/khai3abln.css';
import '../../css/y/ywu8tfbvo.css';
import '../../css/l/llngj8bvv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnKHJubgT"><g class="s9cl3zbei"><path class="aw8asbupg"/><rect class="khai3abln"/><path class="ywu8tfbvo"/><path class="llngj8bvv"/></g></mask></defs><path mask="url(#SVGnKHJubgT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:computer" /></template>
