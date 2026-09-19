<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5e-a9baq.css';
import '../../css/x/xigncxkgn.css';
import '../../css/v/v4lpm3r4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5e-a9baq"/><path class="xigncxkgn"/><path class="v4lpm3r4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:help-book" /></template>
