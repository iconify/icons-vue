<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mfugwt4zs.css';
import '../../css/g/g0lxagb7y.css';
import '../../css/q/qt0k9pbqg.css';
import '../../css/t/tjeo8fbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="mfugwt4zs"/><path class="g0lxagb7y"/><path class="qt0k9pbqg"/><path class="tjeo8fbwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:hospital" /></template>
