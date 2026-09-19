<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blyza-nqz.css';
import '../../css/u/uj15wsh5f.css';
import '../../css/c/ck5nmbc3j.css';
import '../../css/q/q8k-t9rkd.css';
import '../../css/y/ymyjd4bhz.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="blyza-nqz clr-i-solid--badged clr-i-solid-path-1--badged"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged uj15wsh5f"/><path class="ck5nmbc3j clr-i-solid--badged clr-i-solid-path-3--badged"/><path class="clr-i-solid--badged clr-i-solid-path-4--badged q8k-t9rkd"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-5--badged ymyjd4bhz"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:data-cluster-solid-badged" /></template>
