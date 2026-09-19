<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opjpgxw-l.css';
import '../../css/l/liah705zk.css';
import '../../css/q/q9__elwgx.css';
import '../../css/q/q31a-k5ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="opjpgxw-l"/><path class="liah705zk"/><path class="q9__elwgx"/><path class="q31a-k5ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:container-twotone" /></template>
