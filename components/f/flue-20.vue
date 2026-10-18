<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3hdfd1we.css';
import '../../css/s/s6ixhrb8c.css';
import '../../css/l/lz72tab4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n3hdfd1we"/><path class="s6ixhrb8c"/><path class="lz72tab4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flue-20" /></template>
