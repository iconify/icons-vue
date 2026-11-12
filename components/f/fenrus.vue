<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uslf4acad.css';
import '../../css/p/pju2zkapd.css';
import '../../css/t/tvhnkin6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uslf4acad"/><path class="pju2zkapd"/><path class="tvhnkin6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fenrus" /></template>
