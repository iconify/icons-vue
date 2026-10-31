<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y01l-xu0e.css';
import '../../css/d/dzfzn_bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y01l-xu0e"/><path class="dzfzn_bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:lime" /></template>
