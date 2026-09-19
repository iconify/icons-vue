<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu5bcab4r.css';
import '../../css/r/rc_7mwb4l.css';
import '../../css/p/pvoh7sbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu5bcab4r"/><path class="rc_7mwb4l"/><path class="pvoh7sbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:daemon-set-outlined" /></template>
