<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7r_6rw6k.css';
import '../../css/s/sr1rblb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z7r_6rw6k"/><path class="sr1rblb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:film-reel-20" /></template>
