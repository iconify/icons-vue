<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvclzqwjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-car-outline" /></template>
<style>
.tvclzqwjh {
  fill: currentColor;
  d: path("M5 17.5V6zm5.65 3.5q-.179 0-.299-.12t-.12-.3v-5.093l1.271-3.677q.087-.243.289-.392t.469-.149h6.711q.268 0 .47.15q.201.148.288.39L21 15.488v5.094q0 .179-.12.299t-.3.12h-.16q-.18 0-.3-.12t-.12-.3V19.5h-8.77v1.08q0 .18-.12.3t-.298.12zm.777-6.23h8.377l-.894-2.616h-6.59zm1.765 3.25q.367 0 .626-.26q.259-.258.259-.626q0-.367-.259-.625q-.258-.259-.626-.259t-.626.259t-.258.625t.258.626q.259.26.626.26m4.847 0q.367 0 .626-.26q.258-.258.258-.626q0-.367-.258-.625q-.26-.259-.626-.259t-.627.259q-.258.258-.258.625q0 .368.258.626q.26.26.626.26m-6.923.596h9v-2.962h-9zM2 19v-1.5h2V6.616q0-.672.472-1.144T5.616 5h11.769q.67 0 1.143.472q.472.472.472 1.144v2.269h-1v-2.27q0-.269-.173-.442T17.385 6H5.615q-.269 0-.442.173T5 6.616V17.5h2.846V19zm9.116-.385v-2.961z");
}

</style>
