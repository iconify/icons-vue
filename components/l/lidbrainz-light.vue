<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv017rgfy.css';
import '../../css/g/gk9fq7bun.css';
import '../../css/a/a0ch81bxw.css';
import '../../css/n/ntier-hqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gv017rgfy"/><path class="gk9fq7bun"/><path class="a0ch81bxw"/><path class="ntier-hqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lidbrainz-light" /></template>
