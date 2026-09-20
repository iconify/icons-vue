<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox-vypt0m.css';
import '../../css/i/ihwfk3vlx.css';
import '../../css/u/u1_a_s1mm.css';
import '../../css/g/god76-bpw.css';
import '../../css/y/yk-zceb1c.css';
import '../../css/b/b7pjspbss.css';
import '../../css/o/o6sy6lbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ox-vypt0m"/><path class="ihwfk3vlx"/><path class="u1_a_s1mm"/><path class="god76-bpw"/><circle class="yk-zceb1c"/><path class="b7pjspbss"/><path class="o6sy6lbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-alerts-dashboard" /></template>
