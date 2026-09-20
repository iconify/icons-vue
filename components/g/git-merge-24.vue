<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwg56qbut.css';
import '../../css/t/tcv0pgcak.css';
import '../../css/u/ungwd2b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwg56qbut"/><path class="tcv0pgcak"/><path class="ungwd2b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-merge-24" /></template>
