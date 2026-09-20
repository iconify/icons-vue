<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdn-nablh.css';
import '../../css/c/c96m-ibzj.css';
import '../../css/n/n73z5e0fx.css';
import '../../css/r/r7_w2kbdh.css';
import '../../css/w/w9av6_n9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zdn-nablh"/><path class="c96m-ibzj"/><rect class="n73z5e0fx"/><rect class="r7_w2kbdh"/><path class="w9av6_n9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-prompts-open" /></template>
