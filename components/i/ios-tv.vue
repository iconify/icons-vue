<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8p9k171u.css';
import '../../css/x/xx72yyb6l.css';
import '../../css/o/ovoprwbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r8p9k171u"/><path class="xx72yyb6l"/><path class="ovoprwbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-tv" /></template>
