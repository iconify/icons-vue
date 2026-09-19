<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h32t530tv.css';
import '../../css/h/hutuskbuc.css';
import '../../css/n/n9cednr3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h32t530tv"/><path class="hutuskbuc"/><path class="n9cednr3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:disappointed" /></template>
