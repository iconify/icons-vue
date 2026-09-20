<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8zrxk.css';
import '../../css/i/iw1iew.css';
import '../../css/d/d-uxzh.css';
import '../../css/y/y4wbml.css';
import '../../css/i/idmydr.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-20.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8zrxk iw1iew"/><path class="d-uxzh iw1iew y4wbml"/><path class="idmydr iw1iew y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:edit-full-filled" /></template>
