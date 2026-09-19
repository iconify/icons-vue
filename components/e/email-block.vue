<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/x/xs7dh3-er.css';
import '../../css/q/qpbk08zdt.css';
import '../../css/k/kc38scbvr.css';
import '../../css/q/qphacqbpf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJEktceEy"><g class="s9cl3zbei"><path class="xs7dh3-er"/><circle class="qpbk08zdt"/><path class="kc38scbvr"/><path class="qphacqbpf"/></g></mask></defs><path mask="url(#SVGJEktceEy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:email-block" /></template>
