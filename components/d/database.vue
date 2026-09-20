<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb1h9fbba.css';
import '../../css/z/za2wbbz4v.css';
import '../../css/l/ljgnpiurg.css';
import '../../css/o/o-jkj3has.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wb1h9fbba"/><circle class="za2wbbz4v"/><circle class="ljgnpiurg"/><circle class="o-jkj3has"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:database" /></template>
