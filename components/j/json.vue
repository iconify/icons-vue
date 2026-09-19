<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jykbmnblb.css';
import '../../css/k/kpcu7cc2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jykbmnblb"/><path clip-rule="evenodd" class="kpcu7cc2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:json" /></template>
