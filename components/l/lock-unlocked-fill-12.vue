<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg4wcxbgt.css';
import '../../css/b/b-ejs9bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jg4wcxbgt"/><rect class="b-ejs9bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lock-unlocked-fill-12" /></template>
