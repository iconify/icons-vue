<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdl8_lv8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-highlighter-move-outline-rounded" /></template>
<style>
.qdl8_lv8s {
  fill: currentColor;
  d: path("M8.5 4q-.213 0-.357-.143T8 3.5t.143-.357T8.5 3h6.144q.25 0 .372.159q.122.158.122.341t-.125.341t-.375.159zm-3 3.385q-.213 0-.357-.144T5 6.885t.143-.357q.144-.143.357-.143h5.76q.25 0 .372.158q.122.159.122.342q0 .182-.125.341t-.375.159zm-3 3.384q-.213 0-.357-.143T2 10.269t.143-.357t.357-.143h5.375q.25 0 .372.159q.122.158.122.341t-.125.341q-.125.16-.375.16zm12.639 2.923l-2.6-2.6l-4.885 4.885q-.173.173-.173.423t.173.423l1.754 1.754q.173.173.423.173t.423-.173zm-1.887-3.313l2.6 2.6l4.937-4.937q.172-.173.172-.442t-.173-.442l-1.715-1.716q-.173-.173-.442-.173t-.443.173zm-1.062-.354l4.016 4.016l-5.244 5.244q-.485.484-1.131.484T8.7 19.285l-.204-.204l-.907.908q-.131.13-.27.186t-.302.056h-1.47q-.274 0-.37-.252t.096-.444l1.839-1.839l-.166-.165q-.484-.485-.484-1.131t.484-1.13zm0 0l5.31-5.31q.485-.484 1.13-.484t1.132.485l1.753 1.753Q22 6.954 22 7.6t-.484 1.13l-5.31 5.31z");
}

</style>
