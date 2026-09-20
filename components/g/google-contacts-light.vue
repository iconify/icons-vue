<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p64es6bla.css';
import '../../css/f/fx4qy8b3n.css';
import '../../css/w/we___fbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p64es6bla"/><path class="fx4qy8b3n"/><path class="we___fbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-contacts-light" /></template>
